<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/si21m2qws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="si21m2qws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:acquisitions-incorporated" {...props}></Icon>
