<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3eseacbm.css';
import '../../css/n/nc_t_0bbz.css';
import '../../css/a/avq41vbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="d3eseacbm"/><path class="nc_t_0bbz"/><path class="avq41vbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pocketbase" {...props}></Icon>
