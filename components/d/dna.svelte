<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq0tz7xql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gq0tz7xql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:dna" {...props}></Icon>
