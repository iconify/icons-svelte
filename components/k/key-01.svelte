<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-v909bxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-v909bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:key-01" {...props}></Icon>
