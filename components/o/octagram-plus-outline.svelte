<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mj5co-u0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mj5co-u0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:octagram-plus-outline" {...props}></Icon>
