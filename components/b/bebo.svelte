<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kcgzi08rj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":416,"height":488};
const content = `<path class="kcgzi08rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:bebo" {...props}></Icon>
