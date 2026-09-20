<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sccjhlbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sccjhlbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:legal" {...props}></Icon>
