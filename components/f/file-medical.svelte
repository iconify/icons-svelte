<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qm6nu5b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="qm6nu5b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:file-medical" {...props}></Icon>
