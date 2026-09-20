<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slhw7xb9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="slhw7xb9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:call-4" {...props}></Icon>
