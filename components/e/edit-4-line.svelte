<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igc66db3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igc66db3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:edit-4-line" {...props}></Icon>
