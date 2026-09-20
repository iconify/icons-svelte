<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gsgo37b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="gsgo37b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:armchair" {...props}></Icon>
