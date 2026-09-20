<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5citje1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="d5citje1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:radiobox-marked" {...props}></Icon>
