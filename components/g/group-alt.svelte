<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptezw8jtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ptezw8jtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:group-alt" {...props}></Icon>
