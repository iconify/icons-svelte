<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nru-kibmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nru-kibmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:classic-computer" {...props}></Icon>
