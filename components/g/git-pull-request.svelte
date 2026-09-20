<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysw2m96bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ysw2m96bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:git-pull-request" {...props}></Icon>
