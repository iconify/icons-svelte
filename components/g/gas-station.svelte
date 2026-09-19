<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_a8v-fgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":384};
const content = `<path class="h_a8v-fgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:gas-station" {...props}></Icon>
