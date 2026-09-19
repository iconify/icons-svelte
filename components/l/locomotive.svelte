<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlm58cv6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nlm58cv6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:locomotive" {...props}></Icon>
