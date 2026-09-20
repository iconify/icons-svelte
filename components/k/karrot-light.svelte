<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggdcr0-jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ggdcr0-jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:karrot-light" {...props}></Icon>
