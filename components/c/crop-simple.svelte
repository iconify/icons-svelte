<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzobl5bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kzobl5bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:crop-simple" {...props}></Icon>
