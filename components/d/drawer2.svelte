<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nnhtjtfld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nnhtjtfld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:drawer2" {...props}></Icon>
