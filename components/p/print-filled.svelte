<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igsf73ies.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="igsf73ies"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:print-filled" {...props}></Icon>
