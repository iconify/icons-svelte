<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0y87j0bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o0y87j0bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:hand" {...props}></Icon>
