<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-t15ibmv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="d-t15ibmv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-bottom-left-circle" {...props}></Icon>
