<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwjt238zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uwjt238zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:elastic-dark" {...props}></Icon>
