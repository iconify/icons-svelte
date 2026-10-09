<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9is0ybwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y9is0ybwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-rain-48-bold" {...props}></Icon>
