<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebd8ltm4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="ebd8ltm4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:qq" {...props}></Icon>
