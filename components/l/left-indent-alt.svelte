<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi-bafbvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gi-bafbvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:left-indent-alt" {...props}></Icon>
