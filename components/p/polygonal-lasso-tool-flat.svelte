<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8obj5_al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="r8obj5_al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:polygonal-lasso-tool-flat" {...props}></Icon>
