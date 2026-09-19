<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewnc5nb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ewnc5nb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:flask" {...props}></Icon>
