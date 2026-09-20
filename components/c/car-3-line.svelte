<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcw6geb7z.css';
import '../../css/k/k6tg6_vxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vcw6geb7z"/><path class="k6tg6_vxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:car-3-line" {...props}></Icon>
