<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fcnawdb5g.css';
import '../../css/t/tkku46-oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<defs/><path class="fcnawdb5g"/><path class="tkku46-oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:region-analysis-area" {...props}></Icon>
