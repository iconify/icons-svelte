<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib6mbs-7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ib6mbs-7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:opensuse-tumbleweed-light" {...props}></Icon>
