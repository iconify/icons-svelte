<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgo4qfbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tgo4qfbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:round-bottomed-flask" {...props}></Icon>
