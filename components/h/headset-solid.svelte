<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onrhkz8ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="onrhkz8ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:headset-solid" {...props}></Icon>
