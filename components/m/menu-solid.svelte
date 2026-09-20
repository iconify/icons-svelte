<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bx85mubpf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="bx85mubpf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:menu-solid" {...props}></Icon>
