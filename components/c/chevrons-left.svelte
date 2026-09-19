<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_2io5_mv.css';
import '../../css/c/ckipxtbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_2io5_mv"/><path class="ckipxtbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:chevrons-left" {...props}></Icon>
