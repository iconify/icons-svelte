<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhcfrs4ra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="hhcfrs4ra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:gamepad" {...props}></Icon>
