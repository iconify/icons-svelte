<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm5wy70iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm5wy70iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:octagon" {...props}></Icon>
