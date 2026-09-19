<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pclsa0nkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pclsa0nkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:dcn" {...props}></Icon>
