<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_n8-4b8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="p_n8-4b8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-square-down-right" {...props}></Icon>
