<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7p2enbbo.css';
import '../../css/v/v1a49acba.css';
import '../../css/t/tkrg51qty.css';
import '../../css/e/ewv-anbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="k7p2enbbo"/><path class="v1a49acba"/><path class="tkrg51qty"/><path class="ewv-anbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:aruba" {...props}></Icon>
