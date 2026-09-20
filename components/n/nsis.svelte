<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n157im9qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n157im9qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:nsis" {...props}></Icon>
