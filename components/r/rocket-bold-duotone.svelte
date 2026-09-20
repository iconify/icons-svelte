<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/omtfbmb6c.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/e/eub-owb9l.css';
import '../../css/k/kq-ytpe-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="omtfbmb6c"/><g class="mc2zb0bvp"><path class="eub-owb9l"/><path class="kq-ytpe-e"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rocket-bold-duotone" {...props}></Icon>
