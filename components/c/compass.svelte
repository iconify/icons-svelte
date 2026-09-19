<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptg858cvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="ptg858cvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:compass" {...props}></Icon>
