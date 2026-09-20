<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhpb7e10u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="rhpb7e10u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:heavier" {...props}></Icon>
