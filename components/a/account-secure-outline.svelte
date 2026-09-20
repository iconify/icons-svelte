<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_2xycdsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_2xycdsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-secure-outline" {...props}></Icon>
