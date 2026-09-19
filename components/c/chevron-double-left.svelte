<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c55g4gb7e.css';
import '../../css/j/jkx5qo6th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c55g4gb7e"/><path class="jkx5qo6th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:chevron-double-left" {...props}></Icon>
