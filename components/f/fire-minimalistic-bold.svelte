<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nak10dbno.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nak10dbno"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:fire-minimalistic-bold" {...props}></Icon>
