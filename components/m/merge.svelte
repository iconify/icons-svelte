<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igff9lbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="igff9lbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:merge" {...props}></Icon>
