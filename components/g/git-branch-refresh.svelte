<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axu82-ogq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axu82-ogq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:git-branch-refresh" {...props}></Icon>
