<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xxw_zcb4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xxw_zcb4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:magnify-expand" {...props}></Icon>
