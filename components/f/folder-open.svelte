<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acp9e5g1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="acp9e5g1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:folder-open" {...props}></Icon>
