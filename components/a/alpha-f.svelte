<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euyomrbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="euyomrbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-f" {...props}></Icon>
