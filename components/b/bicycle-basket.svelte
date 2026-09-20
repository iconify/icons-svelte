<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grw1hlb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="grw1hlb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bicycle-basket" {...props}></Icon>
