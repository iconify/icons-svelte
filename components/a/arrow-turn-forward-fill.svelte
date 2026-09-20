<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ikp3ozb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ikp3ozb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-turn-forward-fill" {...props}></Icon>
