<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x79jbsbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x79jbsbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:rotation-right-filled" {...props}></Icon>
