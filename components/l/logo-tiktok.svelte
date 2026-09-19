<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oitlfackn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oitlfackn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:logo-tiktok" {...props}></Icon>
