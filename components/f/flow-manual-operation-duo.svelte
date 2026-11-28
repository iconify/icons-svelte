<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cna5h-bpn.css';
import '../../css/k/k5oixywsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cna5h-bpn secondary"/><path class="k5oixywsl primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-manual-operation-duo" {...props}></Icon>
