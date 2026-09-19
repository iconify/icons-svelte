<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go-j6fb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="go-j6fb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:pills" {...props}></Icon>
