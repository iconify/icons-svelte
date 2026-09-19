<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0erngb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0erngb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:equipment-gym-01" {...props}></Icon>
