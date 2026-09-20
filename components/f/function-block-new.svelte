<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4_to2bqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y4_to2bqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:function-block-new" {...props}></Icon>
