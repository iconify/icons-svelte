<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/crw1kccel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="crw1kccel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:qwen-dark" {...props}></Icon>
