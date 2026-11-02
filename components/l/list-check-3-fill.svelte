<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2i4bqgxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2i4bqgxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-check-3-fill" {...props}></Icon>
