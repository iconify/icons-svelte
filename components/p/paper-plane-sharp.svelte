<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-6qv12tf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n-6qv12tf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:paper-plane-sharp" {...props}></Icon>
