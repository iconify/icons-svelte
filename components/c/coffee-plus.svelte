<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bhmjpjbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhmjpjbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:coffee-plus" {...props}></Icon>
