<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p06umcb4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p06umcb4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:chevron-bottom" {...props}></Icon>
