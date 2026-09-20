<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjhrwr1mk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wjhrwr1mk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:compact-disc-solid" {...props}></Icon>
