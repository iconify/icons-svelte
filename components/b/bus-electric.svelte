<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/klt7ieb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="klt7ieb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bus-electric" {...props}></Icon>
