<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pt6j8yqtd.css';
import '../../css/u/ua4c9ibli.css';
import '../../css/t/t418qsbpm.css';
import '../../css/y/yjjibyi4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pt6j8yqtd"/><path class="ua4c9ibli"/><path class="t418qsbpm"/><path class="yjjibyi4l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:reorder-2-line-duotone" {...props}></Icon>
