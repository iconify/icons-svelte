<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4sofebmz.css';
import '../../css/k/ktwj2bcgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k4sofebmz"/><path class="ktwj2bcgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hyvor-relay-dark" {...props}></Icon>
