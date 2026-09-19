<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y17d--b1p.css';
import '../../css/u/u2-ilg5vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y17d--b1p"/><path class="u2-ilg5vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-log-in" {...props}></Icon>
