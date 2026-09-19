<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2lg3s4-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v2lg3s4-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:folder" {...props}></Icon>
