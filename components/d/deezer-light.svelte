<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koxhb4bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="koxhb4bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:deezer-light" {...props}></Icon>
