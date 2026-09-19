<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_9dkpbmu.css';
import '../../css/o/o3b3gk40z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e_9dkpbmu"/><path class="o3b3gk40z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:alarm-sharp" {...props}></Icon>
