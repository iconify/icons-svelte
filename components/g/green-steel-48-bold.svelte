<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hs1xeldxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hs1xeldxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:green-steel-48-bold" {...props}></Icon>
