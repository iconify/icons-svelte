<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euw05tbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="euw05tbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:circle" {...props}></Icon>
