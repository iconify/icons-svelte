<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp6e1w2wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sp6e1w2wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:backspace-sharp" {...props}></Icon>
