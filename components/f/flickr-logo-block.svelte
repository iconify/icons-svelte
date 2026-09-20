<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsl6rs1ix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fsl6rs1ix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:flickr-logo-block" {...props}></Icon>
