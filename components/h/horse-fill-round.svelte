<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq2ci_q3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq2ci_q3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:horse-fill-round" {...props}></Icon>
