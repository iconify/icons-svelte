<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm7he-b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mm7he-b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:controller-record" {...props}></Icon>
