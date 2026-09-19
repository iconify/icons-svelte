<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mccq_k88p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mccq_k88p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bell-check-filled" {...props}></Icon>
