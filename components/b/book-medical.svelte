<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdhe4kbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="gdhe4kbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:book-medical" {...props}></Icon>
