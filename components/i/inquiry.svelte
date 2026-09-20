<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nu-q_73ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nu-q_73ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:inquiry" {...props}></Icon>
