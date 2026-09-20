<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yak4y02xr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yak4y02xr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-tie-hat-outline" {...props}></Icon>
