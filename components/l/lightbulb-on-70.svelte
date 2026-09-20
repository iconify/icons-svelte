<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g7yz59m-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g7yz59m-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:lightbulb-on-70" {...props}></Icon>
