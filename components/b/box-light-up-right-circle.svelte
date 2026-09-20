<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrc83gbvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="wrc83gbvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-up-right-circle" {...props}></Icon>
