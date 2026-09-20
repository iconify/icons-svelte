<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tmryhwkxv.css';
import '../../css/b/b1c8iacsb.css';
import '../../css/n/nxqynyklf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tmryhwkxv"/><path class="b1c8iacsb"/><path class="nxqynyklf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:illustrator" {...props}></Icon>
