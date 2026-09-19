<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wduwcxs0o.css';
import '../../css/s/srcmp7bbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wduwcxs0o"/><path class="srcmp7bbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:make-group" {...props}></Icon>
