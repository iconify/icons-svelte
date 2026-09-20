<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_0ssjbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z_0ssjbti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:perfume" {...props}></Icon>
