<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pinfk8lis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pinfk8lis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:function-2" {...props}></Icon>
