<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kufh5zb-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kufh5zb-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:game-jolt" {...props}></Icon>
