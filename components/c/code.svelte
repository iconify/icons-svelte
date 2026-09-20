<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kgzte6aqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kgzte6aqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:code" {...props}></Icon>
