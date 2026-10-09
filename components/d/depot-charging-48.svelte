<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt3wdaccl.css';
import '../../css/d/d7a8hbbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tt3wdaccl"/><path class="d7a8hbbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:depot-charging-48" {...props}></Icon>
