<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6_x9xmbd.css';
import '../../css/c/c-ivyjb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6_x9xmbd"/><path class="c-ivyjb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alt-arrow-right-bold-duotone" {...props}></Icon>
