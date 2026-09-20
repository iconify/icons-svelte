<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/acg8t5b_l.css';
import '../../css/a/ay1qmvbxn.css';
import '../../css/a/a5du-9wed.css';
import '../../css/q/q6hj83b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="acg8t5b_l"/><path class="ay1qmvbxn"/><path class="a5du-9wed"/><path clip-rule="evenodd" class="q6hj83b4a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:lock-password-outline" {...props}></Icon>
