<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln-p1pbos.css';
import '../../css/p/p8jcaxb6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln-p1pbos"/><path class="p8jcaxb6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chair-bold-duotone" {...props}></Icon>
