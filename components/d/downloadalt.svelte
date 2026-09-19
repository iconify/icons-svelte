<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7ztgisgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="s7ztgisgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:downloadalt" {...props}></Icon>
