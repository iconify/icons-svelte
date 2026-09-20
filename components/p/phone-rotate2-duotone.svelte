<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f2tai6bap.css';
import '../../css/c/cgpqwab7t.css';
import '../../css/p/p_ely1eej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f2tai6bap"/><path class="cgpqwab7t"/><path clip-rule="evenodd" class="p_ely1eej"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:phone-rotate2-duotone" {...props}></Icon>
