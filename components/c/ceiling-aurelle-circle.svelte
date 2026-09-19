<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_ru9otgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t_ru9otgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-aurelle-circle" {...props}></Icon>
