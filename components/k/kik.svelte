<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o4lu-wbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":488};
const content = `<path class="o4lu-wbzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:kik" {...props}></Icon>
