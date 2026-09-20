<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlwl73qmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rlwl73qmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:pkt" {...props}></Icon>
