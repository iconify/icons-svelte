<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzhk1zbhj.css';
import '../../css/a/ann86zbmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzhk1zbhj"/><path class="ann86zbmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:dumbbells-2-bold-duotone" {...props}></Icon>
