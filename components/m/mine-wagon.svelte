<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/micmpg3gk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="micmpg3gk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mine-wagon" {...props}></Icon>
