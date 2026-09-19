<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wds5kfh5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wds5kfh5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:location-x-filled" {...props}></Icon>
