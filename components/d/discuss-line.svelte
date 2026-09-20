<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4280i6sa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4280i6sa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:discuss-line" {...props}></Icon>
