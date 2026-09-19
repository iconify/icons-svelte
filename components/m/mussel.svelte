<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebnm_jb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ebnm_jb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:mussel" {...props}></Icon>
