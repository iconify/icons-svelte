<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqb96mbgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jqb96mbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:rabbit-head" {...props}></Icon>
