<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2u2mlbug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f2u2mlbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hand-reaching-down-to-rough-surface" {...props}></Icon>
