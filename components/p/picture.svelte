<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atxcznbro.css';
import '../../css/k/knpqz8bcw.css';
import '../../css/v/v93089bzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="atxcznbro"/><ellipse class="knpqz8bcw"/><path class="v93089bzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:picture" {...props}></Icon>
