<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq99v4b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq99v4b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dollar-filled" {...props}></Icon>
