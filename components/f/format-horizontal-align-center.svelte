<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6mu9gbof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="p6mu9gbof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:format-horizontal-align-center" {...props}></Icon>
