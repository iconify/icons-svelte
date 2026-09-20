<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4kxr-bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4kxr-bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-box-plus-outline" {...props}></Icon>
