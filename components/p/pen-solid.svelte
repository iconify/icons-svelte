<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro7fx3b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ro7fx3b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pen-solid" {...props}></Icon>
