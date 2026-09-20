<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj4ymt_rb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="wj4ymt_rb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:relative-scale" {...props}></Icon>
