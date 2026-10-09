<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iaeivt5cq.css';
import '../../css/j/j2tlh8boa.css';
import '../../css/r/rv0_ax7fp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iaeivt5cq"/><path class="j2tlh8boa"/><path class="rv0_ax7fp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hourglass-20-bold" {...props}></Icon>
