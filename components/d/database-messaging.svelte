<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nce_cccod.css';
import '../../css/k/khwun-byq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nce_cccod"/><path class="khwun-byq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:database-messaging" {...props}></Icon>
