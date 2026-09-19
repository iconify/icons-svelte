<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jw5nfdb1w.css';
import '../../css/n/nj83mcbyz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jw5nfdb1w"/><path class="nj83mcbyz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dishwasher" {...props}></Icon>
