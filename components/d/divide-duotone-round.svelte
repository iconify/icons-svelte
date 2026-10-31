<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trvs4ey0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="trvs4ey0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:divide-duotone-round" {...props}></Icon>
