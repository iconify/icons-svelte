<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atsojk9me.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="atsojk9me"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:asparagus" {...props}></Icon>
