<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-92dmb1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-92dmb1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:heart-minus" {...props}></Icon>
