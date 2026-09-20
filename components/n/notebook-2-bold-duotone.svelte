<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/h9lgglbqn.css';
import '../../css/g/gijtgjb1f.css';
import '../../css/m/mk1y7bbkx.css';
import '../../css/b/bum4ne1un.css';
import '../../css/p/pg-83zbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h9lgglbqn"/><path class="gijtgjb1f"/><path class="mk1y7bbkx"/><path class="bum4ne1un"/><path class="pg-83zbus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notebook-2-bold-duotone" {...props}></Icon>
