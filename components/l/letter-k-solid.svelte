<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn3hk73hh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rn3hk73hh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-k-solid" {...props}></Icon>
