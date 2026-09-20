<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/at9xv_bjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="at9xv_bjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:qrcode-remove" {...props}></Icon>
