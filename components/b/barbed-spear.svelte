<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq0hqej1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jq0hqej1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:barbed-spear" {...props}></Icon>
