<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-rqccbvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s-rqccbvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:birthday-cake" {...props}></Icon>
