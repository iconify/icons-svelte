<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hctj1nb7c.css';
import '../../css/q/qxaqxeblh.css';
import '../../css/m/mjuiasbra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hctj1nb7c"/><path class="qxaqxeblh"/><path class="mjuiasbra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:package-plus" {...props}></Icon>
