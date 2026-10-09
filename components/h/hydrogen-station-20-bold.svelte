<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azc5oubyv.css';
import '../../css/q/q1hf-4bop.css';
import '../../css/p/pz9jt5fop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="azc5oubyv"/><path class="q1hf-4bop"/><path class="pz9jt5fop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-station-20-bold" {...props}></Icon>
