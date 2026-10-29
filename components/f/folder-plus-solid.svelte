<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ea76pdpsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ea76pdpsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:folder-plus-solid" {...props}></Icon>
