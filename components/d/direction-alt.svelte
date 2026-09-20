<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9yp86lol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="g9yp86lol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:direction-alt" {...props}></Icon>
