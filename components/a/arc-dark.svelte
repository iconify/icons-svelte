<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhb-53bqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":114,"height":46};
const content = `<path class="fhb-53bqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:arc-dark" {...props}></Icon>
