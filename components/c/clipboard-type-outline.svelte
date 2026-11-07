<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxkbezb3a.css';
import '../../css/e/e3rn21oia.css';
import '../../css/t/tv5mrabdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mxkbezb3a"/><path class="e3rn21oia"/><path class="tv5mrabdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-type-outline" {...props}></Icon>
