<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_d2o5wmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j_d2o5wmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:ninja-head" {...props}></Icon>
