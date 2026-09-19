<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb699of5o.css';
import '../../css/s/s397rccgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eb699of5o"/><path class="s397rccgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:logo-nodejs" {...props}></Icon>
