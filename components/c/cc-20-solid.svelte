<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9f2r2p1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="w9f2r2p1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:cc-20-solid" {...props}></Icon>
