<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmjtr9fwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hmjtr9fwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:kite-outline" {...props}></Icon>
