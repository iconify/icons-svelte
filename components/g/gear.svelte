<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jnvz6ub2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jnvz6ub2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:gear" {...props}></Icon>
