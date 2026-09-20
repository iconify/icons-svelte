<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmv-ybh1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmv-ybh1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:brush2-filled" {...props}></Icon>
