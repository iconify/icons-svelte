<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zfoz5e68w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zfoz5e68w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:handbag" {...props}></Icon>
