<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvvj-wvkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvvj-wvkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-mobile-vibration" {...props}></Icon>
