<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjpxx4_bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jjpxx4_bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:greaves" {...props}></Icon>
