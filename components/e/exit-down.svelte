<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4oopynuy.css';
import '../../css/s/sm5_fqxyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="p4oopynuy"/><path class="sm5_fqxyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:exit-down" {...props}></Icon>
