<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/n1c-mrbex.css';
import '../../css/i/iv8ywkbqx.css';
import '../../css/t/tmindebzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="n1c-mrbex"/><path class="iv8ywkbqx"/><path clip-rule="evenodd" class="tmindebzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-lock-bold" {...props}></Icon>
