<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz4u_3b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz4u_3b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-top-left-bold-box-outline" {...props}></Icon>
