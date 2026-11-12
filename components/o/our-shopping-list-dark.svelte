<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n67a_j-wg.css';
import '../../css/q/qjx3e9jap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="n67a_j-wg"/><path class="qjx3e9jap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:our-shopping-list-dark" {...props}></Icon>
