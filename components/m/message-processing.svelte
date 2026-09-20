<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/blxa5_b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="blxa5_b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:message-processing" {...props}></Icon>
