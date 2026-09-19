<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbhv8bbfx.css';
import '../../css/z/z_pgce4lp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sbhv8bbfx"/><path class="z_pgce4lp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-down-left-stroke-circle-filled" {...props}></Icon>
