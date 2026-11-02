<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apss0ie4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="apss0ie4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-small-line" {...props}></Icon>
