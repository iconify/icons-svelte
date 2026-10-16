<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5zgux56h.css';
import '../../css/e/egsafqdij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i5zgux56h"/><path class="egsafqdij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:immersion-heater-20-bold" {...props}></Icon>
