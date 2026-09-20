<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya-wj5bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ya-wj5bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:axe" {...props}></Icon>
