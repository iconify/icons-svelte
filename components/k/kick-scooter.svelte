<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz4dt-pak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zz4dt-pak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:kick-scooter" {...props}></Icon>
