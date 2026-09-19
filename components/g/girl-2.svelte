<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkpfgi2gc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vkpfgi2gc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:girl-2" {...props}></Icon>
