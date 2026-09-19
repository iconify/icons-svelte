<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-mbybois.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z-mbybois"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:medium" {...props}></Icon>
