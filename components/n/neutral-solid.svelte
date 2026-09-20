<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/keq10ib-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="keq10ib-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:neutral-solid" {...props}></Icon>
