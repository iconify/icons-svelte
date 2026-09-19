<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sy3p43tkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sy3p43tkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crescent-blade" {...props}></Icon>
