<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz7zuh0jo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gz7zuh0jo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:database-16" {...props}></Icon>
