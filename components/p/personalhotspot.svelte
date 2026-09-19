<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3dl_ybuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="u3dl_ybuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:personalhotspot" {...props}></Icon>
