<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmhvz6byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rmhvz6byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:clear-all" {...props}></Icon>
