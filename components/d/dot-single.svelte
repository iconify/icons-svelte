<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s96k5zw_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s96k5zw_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:dot-single" {...props}></Icon>
