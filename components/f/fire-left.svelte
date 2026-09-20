<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww_f37bpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="ww_f37bpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:fire-left" {...props}></Icon>
