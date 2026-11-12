<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf5la-bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kf5la-bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:habitat-social-light" {...props}></Icon>
