<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rxq8y6y1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rxq8y6y1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:pictures" {...props}></Icon>
