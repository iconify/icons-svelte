<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9dvpxg2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9dvpxg2u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-down-0-1" {...props}></Icon>
