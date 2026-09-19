<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qfql4b46l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qfql4b46l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:id-card-sharp" {...props}></Icon>
