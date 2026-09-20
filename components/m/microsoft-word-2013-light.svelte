<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqh7--bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bqh7--bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-word-2013-light" {...props}></Icon>
