<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a14f3rbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="a14f3rbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:globe-alt" {...props}></Icon>
