<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2et42jeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="k2et42jeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:bird" {...props}></Icon>
