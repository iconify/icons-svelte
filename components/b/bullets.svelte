<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_dx_-bon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p_dx_-bon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:bullets" {...props}></Icon>
