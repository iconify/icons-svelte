<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blowczb_d.css';
import '../../css/e/e4jz-uehp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="blowczb_d"/><path class="e4jz-uehp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-maximize" {...props}></Icon>
