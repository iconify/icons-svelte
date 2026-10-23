<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7ya5vv3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7ya5vv3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:receipt-japanese-yen" {...props}></Icon>
