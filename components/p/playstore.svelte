<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zm4a30b9t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zm4a30b9t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:playstore" {...props}></Icon>
