<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4ddqwb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t4ddqwb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:profit" {...props}></Icon>
