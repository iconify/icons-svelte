<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9kcw5bsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9kcw5bsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ab-testing" {...props}></Icon>
