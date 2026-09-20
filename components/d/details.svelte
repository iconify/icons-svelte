<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i1m2l6bpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="i1m2l6bpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:details" {...props}></Icon>
