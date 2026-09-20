<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/ma3s7-bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ma3s7-bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dice-2-fill" {...props}></Icon>
