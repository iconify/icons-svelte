<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qge0pjb9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qge0pjb9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:battery-dead-sharp" {...props}></Icon>
