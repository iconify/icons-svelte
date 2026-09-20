<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qpjbsdbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qpjbsdbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:envelope-open" {...props}></Icon>
