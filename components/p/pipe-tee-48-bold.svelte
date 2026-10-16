<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7znocbrd.css';
import '../../css/e/e2r4n70kq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z7znocbrd"/><path class="e2r4n70kq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-tee-48-bold" {...props}></Icon>
