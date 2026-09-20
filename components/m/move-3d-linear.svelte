<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qim-6bkwl.css';
import '../../css/h/h4koblh4d.css';
import '../../css/n/n_9rn8bax.css';
import '../../css/l/l_z-b8vui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qim-6bkwl"/><path class="h4koblh4d"/><path class="n_9rn8bax"/><path class="l_z-b8vui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:move-3d-linear" {...props}></Icon>
