<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbivco96l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hbivco96l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:assembly-cluster" {...props}></Icon>
