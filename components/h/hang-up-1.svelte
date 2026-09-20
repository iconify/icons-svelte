<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka9r9wlnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ka9r9wlnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:hang-up-1" {...props}></Icon>
