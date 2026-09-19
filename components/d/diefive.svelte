<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-rfr86ir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":960,"height":959};
const content = `<path class="s-rfr86ir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:diefive" {...props}></Icon>
