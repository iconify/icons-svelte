<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_wi8bcoy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":896};
const content = `<path class="u_wi8bcoy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:alignleft" {...props}></Icon>
