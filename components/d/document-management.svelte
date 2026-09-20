<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnli30bgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jnli30bgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:document-management" {...props}></Icon>
