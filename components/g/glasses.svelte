<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcr61r1zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qcr61r1zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:glasses" {...props}></Icon>
