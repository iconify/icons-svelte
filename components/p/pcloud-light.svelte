<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecm1oobvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ecm1oobvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pcloud-light" {...props}></Icon>
