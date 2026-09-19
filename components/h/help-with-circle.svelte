<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkved2b9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gkved2b9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:help-with-circle" {...props}></Icon>
