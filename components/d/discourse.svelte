<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zuab840wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zuab840wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:discourse" {...props}></Icon>
