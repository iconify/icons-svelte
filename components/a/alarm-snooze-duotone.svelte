<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lumz9bjgk.css';
import '../../css/p/pbmc5ubjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lumz9bjgk secondary"/><path class="pbmc5ubjw primary"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:alarm-snooze-duotone" {...props}></Icon>
