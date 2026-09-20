<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gk5b0uhxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gk5b0uhxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:card-and-dice" {...props}></Icon>
