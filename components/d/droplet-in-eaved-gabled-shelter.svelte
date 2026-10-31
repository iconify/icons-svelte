<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb4bqhwjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qb4bqhwjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:droplet-in-eaved-gabled-shelter" {...props}></Icon>
