<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8i2_7vnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8i2_7vnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:bacon" {...props}></Icon>
