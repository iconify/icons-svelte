<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjeg35jty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pjeg35jty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fluxer-light" {...props}></Icon>
