<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhrwv_b1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xhrwv_b1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mln" {...props}></Icon>
