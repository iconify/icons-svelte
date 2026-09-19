<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hilva9bwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hilva9bwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pentarrows-tornado" {...props}></Icon>
