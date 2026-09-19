<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tytm7lt4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="tytm7lt4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:power" {...props}></Icon>
