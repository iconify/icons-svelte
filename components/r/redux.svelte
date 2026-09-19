<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnz6y-bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tnz6y-bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:redux" {...props}></Icon>
