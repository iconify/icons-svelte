<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbk-iydcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbk-iydcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:corner-down-left" {...props}></Icon>
