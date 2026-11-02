<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltansw_9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltansw_9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fork-spoon-fill" {...props}></Icon>
