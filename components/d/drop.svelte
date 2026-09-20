<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecktfepqc.css';
import '../../css/q/qd7nioben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ecktfepqc"/><path class="qd7nioben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:drop" {...props}></Icon>
