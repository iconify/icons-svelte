<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sit0q75hg.css';
import '../../css/a/ajb1qznwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sit0q75hg"/><path class="ajb1qznwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:pie-chart-sharp" {...props}></Icon>
