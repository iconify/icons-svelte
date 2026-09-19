<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz50v5bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rz50v5bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-removeformatting" {...props}></Icon>
