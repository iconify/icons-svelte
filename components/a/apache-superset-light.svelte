<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_q8l3bsv.css';
import '../../css/a/agp2gjbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e_q8l3bsv"/><path class="agp2gjbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:apache-superset-light" {...props}></Icon>
