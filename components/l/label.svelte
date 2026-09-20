<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oinc0gbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="oinc0gbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:label" {...props}></Icon>
