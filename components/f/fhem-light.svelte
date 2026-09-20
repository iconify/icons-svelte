<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvpihrqbl.css';
import '../../css/b/bocz3tbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pvpihrqbl"/><path class="bocz3tbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fhem-light" {...props}></Icon>
