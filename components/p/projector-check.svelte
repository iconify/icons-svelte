<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlws5-bvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlws5-bvz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:projector-check" {...props}></Icon>
