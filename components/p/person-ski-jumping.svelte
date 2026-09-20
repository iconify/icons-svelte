<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8pxs_baj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f8pxs_baj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-ski-jumping" {...props}></Icon>
