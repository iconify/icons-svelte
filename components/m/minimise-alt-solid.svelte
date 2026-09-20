<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km668f46e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="km668f46e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:minimise-alt-solid" {...props}></Icon>
