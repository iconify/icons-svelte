<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc3xrub_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rc3xrub_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:inspire" {...props}></Icon>
