<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zslk5ulvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zslk5ulvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:falcon-player-dark" {...props}></Icon>
