<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmaucsqzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmaucsqzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-w-diamond-solid" {...props}></Icon>
