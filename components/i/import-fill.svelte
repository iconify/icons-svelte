<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kmifu0b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kmifu0b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:import-fill" {...props}></Icon>
