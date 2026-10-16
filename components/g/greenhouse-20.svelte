<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mby54wt2i.css';
import '../../css/p/p-azqib5q.css';
import '../../css/m/mn7eeg1uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mby54wt2i"/><path class="p-azqib5q"/><path class="mn7eeg1uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:greenhouse-20" {...props}></Icon>
