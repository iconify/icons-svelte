<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2a3wkb1b.css';
import '../../css/w/wgit70b4c.css';
import '../../css/s/s1d1a8lrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2a3wkb1b"/><path class="wgit70b4c"/><path class="s1d1a8lrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:lightbulb" {...props}></Icon>
