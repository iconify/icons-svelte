<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8uhoz76d.css';
import '../../css/q/q7qow0bez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h8uhoz76d"/><path class="q7qow0bez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:help-circle-sharp" {...props}></Icon>
