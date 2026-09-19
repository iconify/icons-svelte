<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahqt9hblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ahqt9hblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:resize-sharp" {...props}></Icon>
