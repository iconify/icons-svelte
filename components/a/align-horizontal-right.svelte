<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sx2hn-xxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="sx2hn-xxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:align-horizontal-right" {...props}></Icon>
