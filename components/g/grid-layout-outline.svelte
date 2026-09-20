<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjygb7bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="bjygb7bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:grid-layout-outline" {...props}></Icon>
