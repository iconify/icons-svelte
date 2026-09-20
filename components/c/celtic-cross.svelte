<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucdh_db4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ucdh_db4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:celtic-cross" {...props}></Icon>
