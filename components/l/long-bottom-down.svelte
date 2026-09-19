<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m39lfrbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m39lfrbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:long-bottom-down" {...props}></Icon>
