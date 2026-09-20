<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb4me4ebo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="rb4me4ebo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:codepen" {...props}></Icon>
