<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay4scmbps.css';
import '../../css/f/fave5fbdz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ay4scmbps"/><path class="fave5fbdz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-private-path-services" {...props}></Icon>
