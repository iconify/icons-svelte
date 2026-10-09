<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1_q84b1c.css';
import '../../css/f/fzhucbcoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l1_q84b1c"/><path class="fzhucbcoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bowling-20-bold" {...props}></Icon>
