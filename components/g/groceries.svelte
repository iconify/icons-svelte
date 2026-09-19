<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqr_gccre.css';
import '../../css/q/q6az9ltax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b lqr_gccre"/><path class="b q6az9ltax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:groceries" {...props}></Icon>
