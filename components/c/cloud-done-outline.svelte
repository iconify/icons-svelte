<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n4_g4nd3y.css';
import '../../css/g/g7862griq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n4_g4nd3y"/><path class="g7862griq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:cloud-done-outline" {...props}></Icon>
