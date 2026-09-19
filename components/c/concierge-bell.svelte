<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm5ogkonw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jm5ogkonw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:concierge-bell" {...props}></Icon>
