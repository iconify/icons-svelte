<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqy7gsnam.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tqy7gsnam"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:configarr-light" {...props}></Icon>
