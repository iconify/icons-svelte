<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jw65pab4k.css';
import '../../css/i/im9q6tt0h.css';
import '../../css/z/zs0rlhisk.css';
import '../../css/b/ba90tvb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="jw65pab4k"/><path class="im9q6tt0h"/><path clip-rule="evenodd" class="zs0rlhisk"/><path class="ba90tvb7b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:blood-rh-n" {...props}></Icon>
