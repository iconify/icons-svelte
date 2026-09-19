<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1pk1--fd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="o1pk1--fd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:map" {...props}></Icon>
