<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/li3goib3q.css';
import '../../css/b/b4q3fubjb.css';
import '../../css/e/e0cmz0boh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="li3goib3q"/><path class="b4q3fubjb"/><path class="e0cmz0boh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-corrupted-linear" {...props}></Icon>
