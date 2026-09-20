<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibhx10bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibhx10bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-double-right-solid" {...props}></Icon>
