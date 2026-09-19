<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z07rjrbqz.css';
import '../../css/m/m-h11vjnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z07rjrbqz"/><path class="m-h11vjnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:document-outline" {...props}></Icon>
