<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi6qtibex.css';
import '../../css/j/j05r12o9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fi6qtibex"/><path class="j05r12o9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:call-dropped-bold-duotone" {...props}></Icon>
