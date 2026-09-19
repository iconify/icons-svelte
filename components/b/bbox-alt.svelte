<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h31609_ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="h31609_ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:bbox-alt" {...props}></Icon>
