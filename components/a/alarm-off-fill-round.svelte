<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfpyk5bkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qfpyk5bkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:alarm-off-fill-round" {...props}></Icon>
