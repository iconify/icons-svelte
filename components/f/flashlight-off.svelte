<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctiym5e7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-0.5,"top":-0.5};
const content = `<path class="ctiym5e7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:flashlight-off" {...props}></Icon>
