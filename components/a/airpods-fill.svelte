<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epkozqbnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epkozqbnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:airpods-fill" {...props}></Icon>
