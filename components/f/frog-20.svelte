<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ceq48ugul.css';
import '../../css/k/kw7672rxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ceq48ugul"/><path class="kw7672rxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:frog-20" {...props}></Icon>
