<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xou8yqrqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xou8yqrqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-4-1" {...props}></Icon>
