<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0gvujgpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0gvujgpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:circle-dashed-solid" {...props}></Icon>
