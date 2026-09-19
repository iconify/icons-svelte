<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppq6b8bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ppq6b8bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:empty-metal-bucket" {...props}></Icon>
