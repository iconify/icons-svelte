<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm6zm16-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mm6zm16-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:align-top-two" {...props}></Icon>
