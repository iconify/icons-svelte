<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grk1onbae.css';
import '../../css/x/x7xzn4n0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="grk1onbae"/><path class="x7xzn4n0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mouse-48" {...props}></Icon>
