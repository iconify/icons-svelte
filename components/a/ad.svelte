<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvey1b9tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="cvey1b9tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:ad" {...props}></Icon>
