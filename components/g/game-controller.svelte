<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n2tp96bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n2tp96bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:game-controller" {...props}></Icon>
