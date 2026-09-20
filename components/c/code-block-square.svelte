<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfoosl3wn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfoosl3wn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:code-block-square" {...props}></Icon>
