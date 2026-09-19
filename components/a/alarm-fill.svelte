<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rhdob0q5v.css';
import '../../css/x/xli-_5yuc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="rhdob0q5v"/><path class="xli-_5yuc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:alarm-fill" {...props}></Icon>
