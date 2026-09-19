<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz1ow95wt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oz1ow95wt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-badge-dollar" {...props}></Icon>
