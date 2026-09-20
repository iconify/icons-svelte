<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cplin-bse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cplin-bse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:file-no-access-outline" {...props}></Icon>
