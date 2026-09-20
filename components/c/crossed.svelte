<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a35c9ac7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="a35c9ac7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:crossed" {...props}></Icon>
