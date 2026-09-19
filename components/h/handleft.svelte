<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hnszv0-fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":704};
const content = `<path class="hnszv0-fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:handleft" {...props}></Icon>
