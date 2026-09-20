<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu3uspktf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu3uspktf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-minus-outline" {...props}></Icon>
