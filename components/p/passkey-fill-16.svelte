<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra00e7bqq.css';
import '../../css/x/xk-_fybgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ra00e7bqq"/><path class="xk-_fybgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:passkey-fill-16" {...props}></Icon>
