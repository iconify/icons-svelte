<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni-aavqyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ni-aavqyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:crop-1-1-filled" {...props}></Icon>
