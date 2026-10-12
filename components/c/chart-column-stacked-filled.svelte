<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sozdzcb0a.css';
import '../../css/t/tohtuibol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sozdzcb0a"/><path clip-rule="evenodd" class="tohtuibol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:chart-column-stacked-filled" {...props}></Icon>
