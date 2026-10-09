<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sajekru3w.css';
import '../../css/o/olbscvb8w.css';
import '../../css/c/ctg5mublm.css';
import '../../css/q/q4gaqcb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sajekru3w"/><path class="olbscvb8w"/><path class="ctg5mublm"/><path class="q4gaqcb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:battery-symbol-48-bold" {...props}></Icon>
