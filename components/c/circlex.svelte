<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqgw_vb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oqgw_vb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:circlex" {...props}></Icon>
