<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxlpcxeof.css';
import '../../css/d/dg1ec6byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="jxlpcxeof"/><path clip-rule="evenodd" class="dg1ec6byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:folder-alt-duotone-fill" {...props}></Icon>
