<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p38alfs4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="p38alfs4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:projectcompare" {...props}></Icon>
