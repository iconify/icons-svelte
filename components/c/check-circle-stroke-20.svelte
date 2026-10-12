<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m8oetz7xx.css';
import '../../css/f/fdag88jzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m8oetz7xx"/><path class="fdag88jzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-circle-stroke-20" {...props}></Icon>
