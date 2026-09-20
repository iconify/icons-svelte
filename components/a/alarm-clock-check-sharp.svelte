<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov1f3v2im.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ov1f3v2im"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:alarm-clock-check-sharp" {...props}></Icon>
