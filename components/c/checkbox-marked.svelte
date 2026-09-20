<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyaeqib9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="zyaeqib9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:checkbox-marked" {...props}></Icon>
