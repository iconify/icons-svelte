<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha7cf7b5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ha7cf7b5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:megaphone-fill-12" {...props}></Icon>
