<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jocyyo5fc.css';
import '../../css/n/nhe1boyvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jocyyo5fc"/><path class="nhe1boyvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:nozzle-48-bold" {...props}></Icon>
