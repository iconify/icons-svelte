<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nln0yoikt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nln0yoikt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kaunta-dark" {...props}></Icon>
