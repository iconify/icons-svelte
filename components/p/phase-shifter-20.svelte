<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/riu484b2u.css';
import '../../css/j/jbawidbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="riu484b2u"/><path class="jbawidbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phase-shifter-20" {...props}></Icon>
