<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzmubbc_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzmubbc_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-down-bold-circle-outline" {...props}></Icon>
