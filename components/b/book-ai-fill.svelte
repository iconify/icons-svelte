<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqj44p9dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqj44p9dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:book-ai-fill" {...props}></Icon>
