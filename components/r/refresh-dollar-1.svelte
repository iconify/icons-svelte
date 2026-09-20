<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giqgrriek.css';
import '../../css/e/ec7vxwnky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="giqgrriek"/><path class="ec7vxwnky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:refresh-dollar-1" {...props}></Icon>
