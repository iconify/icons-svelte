<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu8u-vlrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vu8u-vlrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:heron" {...props}></Icon>
