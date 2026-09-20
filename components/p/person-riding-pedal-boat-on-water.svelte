<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trevmthyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="trevmthyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-riding-pedal-boat-on-water" {...props}></Icon>
