<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwh3lrbby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="kwh3lrbby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:dot-circle-alt" {...props}></Icon>
