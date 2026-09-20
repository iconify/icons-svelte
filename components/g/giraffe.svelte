<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6190fq_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="y6190fq_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:giraffe" {...props}></Icon>
