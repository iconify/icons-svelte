<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xarwckbam.css';
import '../../css/x/xakjq2afu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xarwckbam"/><path class="xakjq2afu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:prx" {...props}></Icon>
