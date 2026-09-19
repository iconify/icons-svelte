<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3gnn2bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b3gnn2bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:link" {...props}></Icon>
