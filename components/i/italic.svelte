<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr_470bvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qr_470bvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:italic" {...props}></Icon>
