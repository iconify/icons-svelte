<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxbx1y43n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":1024};
const content = `<path class="nxbx1y43n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:planealt" {...props}></Icon>
