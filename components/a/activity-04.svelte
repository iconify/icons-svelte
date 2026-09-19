<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jr7vbsb8z.css';
import '../../css/c/cgdrp4m5c.css';
import '../../css/f/fn9kwg92c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jr7vbsb8z"/><path class="cgdrp4m5c"/><path class="fn9kwg92c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:activity-04" {...props}></Icon>
