<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irq1v8bzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="irq1v8bzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:align-left" {...props}></Icon>
