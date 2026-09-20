<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-tqdrbyb.css';
import '../../css/c/czuk_uaey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g-tqdrbyb"/><path class="czuk_uaey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnifer-bold-duotone" {...props}></Icon>
