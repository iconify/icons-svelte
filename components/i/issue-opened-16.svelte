<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixj357rxr.css';
import '../../css/z/zauqecc_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ixj357rxr"/><path class="zauqecc_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:issue-opened-16" {...props}></Icon>
