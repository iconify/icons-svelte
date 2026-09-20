<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plhb_68gt.css';
import '../../css/x/xwzdy07rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="plhb_68gt"/><path class="xwzdy07rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:external-link" {...props}></Icon>
