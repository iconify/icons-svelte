<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goeb-kbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="goeb-kbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:connect-virtual-machine" {...props}></Icon>
