<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g00oiob2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g00oiob2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:plans" {...props}></Icon>
