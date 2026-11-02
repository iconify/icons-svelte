<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt2ljxb7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt2ljxb7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:report-forms-fill" {...props}></Icon>
