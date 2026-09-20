<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vpi7s0iih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vpi7s0iih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bell-exclamation" {...props}></Icon>
