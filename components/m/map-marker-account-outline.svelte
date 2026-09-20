<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz8oxie2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz8oxie2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:map-marker-account-outline" {...props}></Icon>
