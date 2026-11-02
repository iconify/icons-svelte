<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqx115b0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqx115b0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gallery-vertical-line" {...props}></Icon>
