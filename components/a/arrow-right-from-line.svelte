<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sa48ywbkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sa48ywbkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:arrow-right-from-line" {...props}></Icon>
