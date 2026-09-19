<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b45ykkjsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b45ykkjsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:next-button" {...props}></Icon>
