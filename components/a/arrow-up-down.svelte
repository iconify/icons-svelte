<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyyg_11vl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="tyyg_11vl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-up-down" {...props}></Icon>
