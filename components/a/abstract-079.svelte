<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npi5k6g5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="npi5k6g5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:abstract-079" {...props}></Icon>
