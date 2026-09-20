<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt0grkbak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xt0grkbak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:crossing-tram-solid" {...props}></Icon>
