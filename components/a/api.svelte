<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbs9_-1an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbs9_-1an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:api" {...props}></Icon>
