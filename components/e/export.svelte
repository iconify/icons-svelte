<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n74n5ebcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n74n5ebcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:export" {...props}></Icon>
