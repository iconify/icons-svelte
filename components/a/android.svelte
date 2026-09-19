<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oftap6bxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oftap6bxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:android" {...props}></Icon>
