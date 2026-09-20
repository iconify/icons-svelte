<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r800l5baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="r800l5baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:linen" {...props}></Icon>
