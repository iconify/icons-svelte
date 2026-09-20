<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti463us-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti463us-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:grip-horizontal-solid" {...props}></Icon>
