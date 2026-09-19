<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ehliqybph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ehliqybph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:door-watcher" {...props}></Icon>
