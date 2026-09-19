<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob0g1dvlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ob0g1dvlc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:diamond-minus" {...props}></Icon>
