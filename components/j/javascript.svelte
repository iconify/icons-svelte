<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw90tlbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fw90tlbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:javascript" {...props}></Icon>
