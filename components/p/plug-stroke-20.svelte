<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hawd1sbrw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hawd1sbrw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:plug-stroke-20" {...props}></Icon>
