<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2hdh4u_p.css';
import '../../css/u/uoq1u0bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r2hdh4u_p"/><path class="uoq1u0bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:home-duotone" {...props}></Icon>
