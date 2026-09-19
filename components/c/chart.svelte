<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9_xqx6dr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y9_xqx6dr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:chart" {...props}></Icon>
