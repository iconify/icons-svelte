<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxaj67-zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="zxaj67-zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:gym" {...props}></Icon>
