<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb1h9rbig.css';
import '../../css/d/dglb7bs3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb1h9rbig"/><path class="dglb7bs3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:no-dollars-filled" {...props}></Icon>
