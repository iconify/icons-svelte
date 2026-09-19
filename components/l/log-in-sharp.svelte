<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp3l25kpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zp3l25kpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:log-in-sharp" {...props}></Icon>
