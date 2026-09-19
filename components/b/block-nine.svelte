<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dhl620mrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dhl620mrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:block-nine" {...props}></Icon>
