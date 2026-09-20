<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/idebgla5y.css';
import '../../css/y/y16o0oyvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="idebgla5y"/><path class="y16o0oyvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:image-filled" {...props}></Icon>
