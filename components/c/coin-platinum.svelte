<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hf92albeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="hf92albeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:coin-platinum" {...props}></Icon>
