<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekc2msb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ekc2msb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:key-1-line" {...props}></Icon>
