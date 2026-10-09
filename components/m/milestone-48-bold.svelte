<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rv2a2jbrl.css';
import '../../css/x/x41cd7j7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rv2a2jbrl"/><path class="x41cd7j7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:milestone-48-bold" {...props}></Icon>
