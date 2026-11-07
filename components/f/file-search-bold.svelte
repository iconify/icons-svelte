<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oio3n0tpv.css';
import '../../css/n/nka8deypl.css';
import '../../css/w/wm3j448rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oio3n0tpv"/><path clip-rule="evenodd" class="nka8deypl"/><path class="wm3j448rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-search-bold" {...props}></Icon>
