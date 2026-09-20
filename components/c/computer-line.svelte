<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck30kberr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck30kberr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:computer-line" {...props}></Icon>
