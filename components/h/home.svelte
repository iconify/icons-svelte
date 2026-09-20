<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2hdh4u_p.css';
import '../../css/p/p7m4fxbob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2hdh4u_p"/><path class="p7m4fxbob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:home" {...props}></Icon>
