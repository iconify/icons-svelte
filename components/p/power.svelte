<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usac0up9h.css';
import '../../css/b/bo0bdiq0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="usac0up9h"/><path class="bo0bdiq0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:power" {...props}></Icon>
