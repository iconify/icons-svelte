<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6qgsn_0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":25};
const content = `<path class="u6qgsn_0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:references" {...props}></Icon>
