<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lta4h9b0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lta4h9b0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:addthis" {...props}></Icon>
