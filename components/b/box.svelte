<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k19gm4bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k19gm4bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:box" {...props}></Icon>
