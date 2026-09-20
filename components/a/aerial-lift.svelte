<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mms7eybus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mms7eybus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:aerial-lift" {...props}></Icon>
