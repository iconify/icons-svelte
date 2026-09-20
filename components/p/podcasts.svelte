<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3t4qwbjm.css';
import '../../css/b/b5_gm_r9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3t4qwbjm"/><path class="b5_gm_r9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:podcasts" {...props}></Icon>
