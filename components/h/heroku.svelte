<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulra56alq.css';
import '../../css/w/w03w98eed.css';
import '../../css/v/v5k322mny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="ulra56alq"><path class="w03w98eed"/><path class="v5k322mny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:heroku" {...props}></Icon>
