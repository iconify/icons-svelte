<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt-su-b9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lt-su-b9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:double-chevron-up" {...props}></Icon>
