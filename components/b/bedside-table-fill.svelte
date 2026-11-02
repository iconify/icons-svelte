<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suzek1byy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="suzek1byy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bedside-table-fill" {...props}></Icon>
