<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/od84yrbfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="od84yrbfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:javascript-solid" {...props}></Icon>
