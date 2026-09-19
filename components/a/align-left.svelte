<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9upf7bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="v9upf7bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:align-left" {...props}></Icon>
