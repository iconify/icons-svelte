<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xukl73g2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xukl73g2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:plus-circle-stroke-20" {...props}></Icon>
