<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdttf1bqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fdttf1bqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:circle-dot-filled" {...props}></Icon>
