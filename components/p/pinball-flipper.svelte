<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oo09xl7mi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oo09xl7mi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:pinball-flipper" {...props}></Icon>
