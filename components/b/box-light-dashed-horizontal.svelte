<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w--j_2sqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="w--j_2sqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-dashed-horizontal" {...props}></Icon>
