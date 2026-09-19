<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4-dp5bws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v4-dp5bws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:hotel" {...props}></Icon>
