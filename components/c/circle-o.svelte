<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ek2nfs3nb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ek2nfs3nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:circle-o" {...props}></Icon>
