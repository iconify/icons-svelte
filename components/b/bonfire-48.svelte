<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm29_vbfv.css';
import '../../css/q/q534ik57i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pm29_vbfv"/><path class="q534ik57i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bonfire-48" {...props}></Icon>
