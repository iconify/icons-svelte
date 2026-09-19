<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfgxx8b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="lfgxx8b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:failed" {...props}></Icon>
