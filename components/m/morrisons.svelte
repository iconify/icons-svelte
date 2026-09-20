<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyf_zsblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyf_zsblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:morrisons" {...props}></Icon>
