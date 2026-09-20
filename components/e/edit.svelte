<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5u_hrb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m5u_hrb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:edit" {...props}></Icon>
