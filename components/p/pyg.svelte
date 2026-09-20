<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pf7b53bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pf7b53bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pyg" {...props}></Icon>
