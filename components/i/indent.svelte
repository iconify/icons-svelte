<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3ubk7gcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p3ubk7gcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:indent" {...props}></Icon>
