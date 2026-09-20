<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2206v69j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2206v69j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-left-up-box-line" {...props}></Icon>
