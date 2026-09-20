<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g45a4ubfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g45a4ubfc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-mobile-cancel" {...props}></Icon>
