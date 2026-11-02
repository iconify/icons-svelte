<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khx4plw-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khx4plw-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hiking-line" {...props}></Icon>
