<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr5jt2bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="wr5jt2bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:checkbox-cross" {...props}></Icon>
