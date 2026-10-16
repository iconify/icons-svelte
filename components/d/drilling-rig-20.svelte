<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jbd13vizc.css';
import '../../css/i/imtkfjwmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jbd13vizc"/><path class="imtkfjwmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drilling-rig-20" {...props}></Icon>
