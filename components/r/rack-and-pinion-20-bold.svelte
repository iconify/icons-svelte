<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bryv9-bhw.css';
import '../../css/e/eakappb5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bryv9-bhw"/><path class="eakappb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rack-and-pinion-20-bold" {...props}></Icon>
