<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gngoa7gvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="gngoa7gvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:book" {...props}></Icon>
