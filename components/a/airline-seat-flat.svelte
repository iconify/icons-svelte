<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w72bjhbff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="w72bjhbff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:airline-seat-flat" {...props}></Icon>
