<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xszr6whvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xszr6whvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-big-left" {...props}></Icon>
