<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwi16yuep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iwi16yuep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chevron-down-right-solid" {...props}></Icon>
