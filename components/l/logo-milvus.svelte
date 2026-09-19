<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq9s03bgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tq9s03bgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-milvus" {...props}></Icon>
