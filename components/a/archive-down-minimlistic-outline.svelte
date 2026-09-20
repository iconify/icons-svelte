<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydol6mbyu.css';
import '../../css/r/r8h9qdcac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ydol6mbyu"/><path clip-rule="evenodd" class="r8h9qdcac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:archive-down-minimlistic-outline" {...props}></Icon>
