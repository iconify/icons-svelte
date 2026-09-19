<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vn6ew33jm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vn6ew33jm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:filter-mail" {...props}></Icon>
