<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hed_-cccn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hed_-cccn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:mail" {...props}></Icon>
