<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ct-exp8sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ct-exp8sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:circle-close-o" {...props}></Icon>
