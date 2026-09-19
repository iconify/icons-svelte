<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6m34_-qc.css';
import '../../css/i/ifltctg4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y6m34_-qc"/><path class="ifltctg4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:electro-devices" {...props}></Icon>
