<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfk3trb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kfk3trb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:bem" {...props}></Icon>
