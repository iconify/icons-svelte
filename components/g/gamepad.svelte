<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlo9x92kx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wlo9x92kx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:gamepad" {...props}></Icon>
