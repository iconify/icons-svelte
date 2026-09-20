<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxi8d7bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vxi8d7bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:folder-x-outline" {...props}></Icon>
