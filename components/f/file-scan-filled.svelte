<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmg9y89jt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dmg9y89jt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:file-scan-filled" {...props}></Icon>
