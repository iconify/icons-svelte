<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4ko08bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="c4ko08bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:envelope-square" {...props}></Icon>
