<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv5s3x1eu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":16};
const content = `<path class="dv5s3x1eu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:location" {...props}></Icon>
