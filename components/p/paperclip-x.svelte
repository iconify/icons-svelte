<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x34ym-b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x34ym-b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:paperclip-x" {...props}></Icon>
