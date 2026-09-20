<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pwo5oobls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pwo5oobls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:border-outer-outline" {...props}></Icon>
