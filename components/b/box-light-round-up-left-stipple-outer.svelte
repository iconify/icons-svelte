<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt42iebzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="bt42iebzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-round-up-left-stipple-outer" {...props}></Icon>
