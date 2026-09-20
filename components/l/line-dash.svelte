<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvogwvb9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jvogwvb9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:line-dash" {...props}></Icon>
