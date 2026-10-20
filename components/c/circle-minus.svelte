<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcmrqu1vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dcmrqu1vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:circle-minus" {...props}></Icon>
