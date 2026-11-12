<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z05v8zbft.css';
import '../../css/h/hpvm9bcft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z05v8zbft"/><path class="hpvm9bcft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cr-nmaster-dark" {...props}></Icon>
