<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcfp9s-0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGt6KFdcQE" class="wcfp9s-0x"/></defs><use href="#SVGt6KFdcQE"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:notice-push" {...props}></Icon>
