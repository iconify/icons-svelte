<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y864t2bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y864t2bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:envelope-open" {...props}></Icon>
