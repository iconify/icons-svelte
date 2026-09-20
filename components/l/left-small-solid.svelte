<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zut3d2byv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zut3d2byv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:left-small-solid" {...props}></Icon>
