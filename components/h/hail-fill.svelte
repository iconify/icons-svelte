<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im5_q7b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="im5_q7b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hail-fill" {...props}></Icon>
