<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7nujkzvg.css';
import '../../css/u/u9y3aibok.css';
import '../../css/v/vf6i915qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j7nujkzvg"/><path class="u9y3aibok"/><path class="vf6i915qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dsm" {...props}></Icon>
