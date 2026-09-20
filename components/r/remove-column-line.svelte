<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss8-hublk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ss8-hublk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:remove-column-line" {...props}></Icon>
