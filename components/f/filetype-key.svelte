<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he0zjtgwt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="he0zjtgwt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-key" {...props}></Icon>
