<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk05hr1jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gk05hr1jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:arrows-horizontal" {...props}></Icon>
