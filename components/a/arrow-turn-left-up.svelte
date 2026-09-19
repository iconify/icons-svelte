<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekmislbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ekmislbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:arrow-turn-left-up" {...props}></Icon>
