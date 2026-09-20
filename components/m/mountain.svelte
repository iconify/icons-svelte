<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhc6vccdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fhc6vccdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:mountain" {...props}></Icon>
