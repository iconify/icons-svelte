<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uif2hsb6m.css';
import '../../css/m/m-2igxbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uif2hsb6m"/><path class="m-2igxbdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:leaf-outline" {...props}></Icon>
