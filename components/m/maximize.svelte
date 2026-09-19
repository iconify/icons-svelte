<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfuiahb8m.css';
import '../../css/d/dnd7e2h4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tfuiahb8m"/><path class="dnd7e2h4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:maximize" {...props}></Icon>
