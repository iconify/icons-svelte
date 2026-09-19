<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvc1t2bhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="xvc1t2bhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:hive" {...props}></Icon>
