<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg9m1iqrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fg9m1iqrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:file-woff2-filled" {...props}></Icon>
