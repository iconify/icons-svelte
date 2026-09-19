<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4xo2jmoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="v4xo2jmoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:icp" {...props}></Icon>
