<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx9sq5pnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jx9sq5pnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:edit-code" {...props}></Icon>
