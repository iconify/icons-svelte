<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zwam_sbkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":16};
const content = `<path class="zwam_sbkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:key" {...props}></Icon>
