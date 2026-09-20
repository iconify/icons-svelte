<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stsixlbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="stsixlbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:aspect-ratio" {...props}></Icon>
