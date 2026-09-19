<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn7bfp_tc.css';
import '../../css/t/tfentzbbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn7bfp_tc"/><circle class="tfentzbbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:palette" {...props}></Icon>
