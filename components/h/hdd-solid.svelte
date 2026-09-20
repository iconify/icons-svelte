<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2p3ih6-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k2p3ih6-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hdd-solid" {...props}></Icon>
