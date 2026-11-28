<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mywlo63po.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mywlo63po"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-off" {...props}></Icon>
