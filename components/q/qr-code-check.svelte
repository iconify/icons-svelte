<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owynusbds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owynusbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:qr-code-check" {...props}></Icon>
