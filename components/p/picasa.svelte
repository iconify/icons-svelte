<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz7hrwbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bz7hrwbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:picasa" {...props}></Icon>
