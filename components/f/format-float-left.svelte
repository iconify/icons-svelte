<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbrxdcbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbrxdcbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:format-float-left" {...props}></Icon>
