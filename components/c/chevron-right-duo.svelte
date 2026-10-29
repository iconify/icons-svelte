<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgo5kz4zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgo5kz4zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:chevron-right-duo" {...props}></Icon>
