<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gie6qpbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gie6qpbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:align-left-solid" {...props}></Icon>
