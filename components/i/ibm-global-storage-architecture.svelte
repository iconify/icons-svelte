<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poga9shhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="poga9shhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-global-storage-architecture" {...props}></Icon>
