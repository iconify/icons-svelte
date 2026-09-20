<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvz8k-fun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvz8k-fun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:front-windshield-defroster-fill" {...props}></Icon>
