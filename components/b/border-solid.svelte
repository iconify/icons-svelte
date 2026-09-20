<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhwk81qdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fhwk81qdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:border-solid" {...props}></Icon>
