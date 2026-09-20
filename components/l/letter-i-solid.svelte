<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az_f5k7uo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="az_f5k7uo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-i-solid" {...props}></Icon>
