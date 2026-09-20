<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epcos0d9j.css';
import '../../css/o/ocymuzb7a.css';
import '../../css/x/x6uuzdbii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="epcos0d9j"/><path class="ocymuzb7a"/><path class="x6uuzdbii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:computers-devices-electronics-tablet" {...props}></Icon>
