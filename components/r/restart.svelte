<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxk_-ubon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pxk_-ubon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:restart" {...props}></Icon>
