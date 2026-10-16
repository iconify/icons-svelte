<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-e81vb3y.css';
import '../../css/n/nlgovibwp.css';
import '../../css/e/ek-1xpvww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i-e81vb3y"/><path class="nlgovibwp"/><path class="ek-1xpvww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pcb-20" {...props}></Icon>
