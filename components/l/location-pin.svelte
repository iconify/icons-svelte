<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yyatedb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="yyatedb_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:location-pin" {...props}></Icon>
