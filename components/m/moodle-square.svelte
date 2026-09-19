<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwzby5b2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="kwzby5b2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:moodle-square" {...props}></Icon>
