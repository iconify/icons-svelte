<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4pk15lrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d4pk15lrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:oot" {...props}></Icon>
