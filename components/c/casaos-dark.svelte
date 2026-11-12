<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcohwfb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qcohwfb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:casaos-dark" {...props}></Icon>
