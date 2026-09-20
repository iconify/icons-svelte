<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhlg9b33u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="rhlg9b33u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:drag-solid" {...props}></Icon>
