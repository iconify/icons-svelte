<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdvf5flpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sdvf5flpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:checkbox-filled" {...props}></Icon>
