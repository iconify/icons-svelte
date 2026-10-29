<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll9t1wp4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ll9t1wp4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:orbit" {...props}></Icon>
