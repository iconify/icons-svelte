<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atb0_abao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="atb0_abao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-bottom-right" {...props}></Icon>
