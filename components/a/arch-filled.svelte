<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fetyxpbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fetyxpbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arch-filled" {...props}></Icon>
