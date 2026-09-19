<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8b5m4b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="s8b5m4b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:open-data-square" {...props}></Icon>
