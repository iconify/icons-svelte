<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l86i2yr1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l86i2yr1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:medal-alt-2" {...props}></Icon>
