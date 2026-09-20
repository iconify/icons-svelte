<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf8tgcb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf8tgcb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:body-scan-fill" {...props}></Icon>
