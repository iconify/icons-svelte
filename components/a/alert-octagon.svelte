<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq4gl78ho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="jq4gl78ho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:alert-octagon" {...props}></Icon>
