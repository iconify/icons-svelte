<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pju4p0r6w.css';
import '../../css/n/n8yz9-5xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pju4p0r6w"/><path class="n8yz9-5xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chevrons-up-48-bold" {...props}></Icon>
