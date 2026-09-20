<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goyprba4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="goyprba4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alert-circle" {...props}></Icon>
