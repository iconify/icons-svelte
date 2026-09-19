<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwx32-blf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwx32-blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:balcony-filled" {...props}></Icon>
