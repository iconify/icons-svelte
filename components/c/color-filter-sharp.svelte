<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfqjsdbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gfqjsdbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:color-filter-sharp" {...props}></Icon>
