<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnmfwi88a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnmfwi88a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:delete-alert" {...props}></Icon>
