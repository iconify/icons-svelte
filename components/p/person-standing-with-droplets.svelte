<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq7cyxzqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gq7cyxzqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-standing-with-droplets" {...props}></Icon>
