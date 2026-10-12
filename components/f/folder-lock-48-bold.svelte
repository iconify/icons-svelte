<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywyo2sv2k.css';
import '../../css/w/wub_f-bbi.css';
import '../../css/u/uir1vq-bm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ywyo2sv2k"/><path class="wub_f-bbi"/><path class="uir1vq-bm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-lock-48-bold" {...props}></Icon>
