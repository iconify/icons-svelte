<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9xv_7bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="q9xv_7bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:lightning-outline" {...props}></Icon>
