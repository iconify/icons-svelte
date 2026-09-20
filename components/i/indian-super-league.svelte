<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soa5_dbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="soa5_dbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:indian-super-league" {...props}></Icon>
