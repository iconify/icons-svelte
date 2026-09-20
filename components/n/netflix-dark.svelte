<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq2kp497d.css';
import '../../css/k/krjjutbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wq2kp497d"/><path class="krjjutbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:netflix-dark" {...props}></Icon>
