<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-0xmhb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u-0xmhb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:gitter" {...props}></Icon>
