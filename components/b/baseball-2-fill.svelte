<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpszd2bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpszd2bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:baseball-2-fill" {...props}></Icon>
