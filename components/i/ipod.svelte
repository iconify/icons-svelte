<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qphc-ub_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":1024};
const content = `<path class="qphc-ub_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:ipod" {...props}></Icon>
