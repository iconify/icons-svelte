<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s7_g47bqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s7_g47bqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:icons" {...props}></Icon>
