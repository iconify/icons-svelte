<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hy0q690mc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hy0q690mc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:pencil" {...props}></Icon>
