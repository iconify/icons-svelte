<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sozdzcb0a.css';
import '../../css/r/ris-r3boe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sozdzcb0a"/><path clip-rule="evenodd" class="ris-r3boe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:chart-bar-stacked-filled" {...props}></Icon>
