<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m68lqw2ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m68lqw2ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rear-windshield-defroster-fill" {...props}></Icon>
