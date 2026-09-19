<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/estb-abdk.css';
import '../../css/d/dicdvz1vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="estb-abdk"/><path class="dicdvz1vu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:qa-4x3" {...props}></Icon>
