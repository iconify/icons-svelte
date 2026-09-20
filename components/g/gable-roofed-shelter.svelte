<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wtv-45bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wtv-45bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gable-roofed-shelter" {...props}></Icon>
