<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dssqhxb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dssqhxb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pencil-line-fill-round" {...props}></Icon>
