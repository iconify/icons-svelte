<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if349kbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="if349kbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:framer" {...props}></Icon>
