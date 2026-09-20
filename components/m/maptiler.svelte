<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd6pvxbcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd6pvxbcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:maptiler" {...props}></Icon>
