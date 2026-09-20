<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_h32ggwa.css';
import '../../css/y/yka_8gutb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j_h32ggwa"/><path class="yka_8gutb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:office-file-graph-bold" {...props}></Icon>
