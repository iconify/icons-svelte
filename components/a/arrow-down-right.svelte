<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxqvby7nx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxqvby7nx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-down-right" {...props}></Icon>
