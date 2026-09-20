<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4r41fb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4r41fb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:letters-q" {...props}></Icon>
