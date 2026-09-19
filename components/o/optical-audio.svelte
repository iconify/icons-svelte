<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/ddk587bmb.css';
import '../../css/w/wtyo39cge.css';
import '../../css/v/vuct_acof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="ddk587bmb"/><path class="wtyo39cge"/><path class="vuct_acof"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:optical-audio" {...props}></Icon>
