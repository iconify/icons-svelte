<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zil8_rj-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zil8_rj-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:refrigerator" {...props}></Icon>
