<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt_ut7wjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dt_ut7wjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:banana" {...props}></Icon>
