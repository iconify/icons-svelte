<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0mjtcctz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0mjtcctz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bookmark-02" {...props}></Icon>
