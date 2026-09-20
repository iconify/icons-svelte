<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltx-teboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ltx-teboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-lab-fill" {...props}></Icon>
