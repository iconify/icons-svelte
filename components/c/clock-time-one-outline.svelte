<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy60gyb7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gy60gyb7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-one-outline" {...props}></Icon>
