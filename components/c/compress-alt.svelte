<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nza448bsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="nza448bsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:compress-alt" {...props}></Icon>
