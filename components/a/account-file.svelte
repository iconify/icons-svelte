<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6g2lnbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6g2lnbqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-file" {...props}></Icon>
