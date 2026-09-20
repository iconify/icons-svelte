<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2nqqvsmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="v2nqqvsmk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:gentleman" {...props}></Icon>
