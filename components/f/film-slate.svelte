<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvn_bpb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="vvn_bpb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:film-slate" {...props}></Icon>
