<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygz1y6bnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ygz1y6bnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:headset-off-sharp" {...props}></Icon>
