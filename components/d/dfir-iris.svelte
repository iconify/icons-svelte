<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kok4w2blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kok4w2blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dfir-iris" {...props}></Icon>
