<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0oa-qzdz.css';
import '../../css/r/rji5c601e.css';
import '../../css/t/ttfadacqv.css';
import '../../css/n/n3c3iru4h.css';
import '../../css/g/gmq7wzbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c0oa-qzdz"/><path class="rji5c601e"/><path class="ttfadacqv"/><path class="n3c3iru4h"/><path class="gmq7wzbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:accessibility-20-bold" {...props}></Icon>
