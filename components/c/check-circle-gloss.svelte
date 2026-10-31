<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/me2gmwbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="me2gmwbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:check-circle-gloss" {...props}></Icon>
