<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qonqq2zjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qonqq2zjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:copy-stroke-12" {...props}></Icon>
