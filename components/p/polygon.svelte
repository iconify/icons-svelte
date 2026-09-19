<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwa5up2ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lwa5up2ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:polygon" {...props}></Icon>
