<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqoty1doq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mqoty1doq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:drone-ci" {...props}></Icon>
