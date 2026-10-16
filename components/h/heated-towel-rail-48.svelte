<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm-t92b-g.css';
import '../../css/s/s-ndftb7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tm-t92b-g"/><path class="s-ndftb7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heated-towel-rail-48" {...props}></Icon>
