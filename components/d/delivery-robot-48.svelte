<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-rt1kbiq.css';
import '../../css/m/msqhepy4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f-rt1kbiq"/><path class="msqhepy4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:delivery-robot-48" {...props}></Icon>
