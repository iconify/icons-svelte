<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwuk1ybsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pwuk1ybsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:circle-down" {...props}></Icon>
