<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgxehxbmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sgxehxbmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-top-right-alt" {...props}></Icon>
