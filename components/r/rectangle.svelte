<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbe9ikuca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbe9ikuca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:rectangle" {...props}></Icon>
