<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwv6sm2lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qwv6sm2lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:font-outline" {...props}></Icon>
