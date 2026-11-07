<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/osfbwubry.css';
import '../../css/q/qafvmubuv.css';
import '../../css/j/jyumk6b3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="osfbwubry"/><path class="qafvmubuv"/><path class="jyumk6b3q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:kanban-line-duotone" {...props}></Icon>
