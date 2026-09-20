<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pftvle2xc.css';
import '../../css/c/cxuk12djg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pftvle2xc"/><path class="cxuk12djg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:feed-issue-open-16" {...props}></Icon>
