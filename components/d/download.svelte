<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bqg22qc_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bqg22qc_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:download" {...props}></Icon>
