<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-8v5fp5o.css';
import '../../css/h/hwjgqrbah.css';
import '../../css/i/it04kcbvr.css';
import '../../css/g/gsyd5vmtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l-8v5fp5o"/><path class="hwjgqrbah"/><path class="it04kcbvr"/><path class="gsyd5vmtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-plus-48-bold" {...props}></Icon>
