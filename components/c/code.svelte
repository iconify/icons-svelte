<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/po-nq2spx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1856,"height":1408};
const content = `<path class="po-nq2spx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:code" {...props}></Icon>
