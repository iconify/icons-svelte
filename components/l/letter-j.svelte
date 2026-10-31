<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq4wvbcag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq4wvbcag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:letter-j" {...props}></Icon>
