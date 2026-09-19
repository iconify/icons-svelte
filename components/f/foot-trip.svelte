<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3ozll52o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b3ozll52o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:foot-trip" {...props}></Icon>
