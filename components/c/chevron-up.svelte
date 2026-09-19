<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m63-p253l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="m63-p253l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:chevron-up" {...props}></Icon>
