<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o5i5-sbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o5i5-sbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:diamond" {...props}></Icon>
