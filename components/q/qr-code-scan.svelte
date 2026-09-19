<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/typ1igblf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="typ1igblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:qr-code-scan" {...props}></Icon>
