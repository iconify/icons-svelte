<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc0s-3bss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uc0s-3bss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:crowdsec-light" {...props}></Icon>
