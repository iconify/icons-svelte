<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zaoe0hbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zaoe0hbtt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:anomaly" {...props}></Icon>
