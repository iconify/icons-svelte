<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tnmw1ju5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tnmw1ju5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-box-multiple-outline" {...props}></Icon>
