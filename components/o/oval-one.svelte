<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ep9shg-nt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="ep9shg-nt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:oval-one" {...props}></Icon>
