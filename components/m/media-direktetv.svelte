<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx13v7buv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hx13v7buv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:media-direktetv" {...props}></Icon>
