<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfcz9ib6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfcz9ib6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:geopandas" {...props}></Icon>
