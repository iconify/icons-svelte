<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi9w2m9_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="oi9w2m9_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:jump" {...props}></Icon>
