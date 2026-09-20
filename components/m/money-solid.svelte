<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu5lx12xc.css';
import '../../css/v/v3045wb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gu5lx12xc"/><path clip-rule="evenodd" class="v3045wb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:money-solid" {...props}></Icon>
