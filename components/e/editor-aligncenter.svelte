<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alnok1cnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="alnok1cnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-aligncenter" {...props}></Icon>
