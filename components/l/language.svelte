<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gog_lij3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="gog_lij3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:language" {...props}></Icon>
