<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7wlu5qtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="o7wlu5qtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:gable-roofed-building" {...props}></Icon>
