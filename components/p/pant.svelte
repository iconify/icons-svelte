<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czvroobwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":520};
const content = `<path class="czvroobwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:pant" {...props}></Icon>
