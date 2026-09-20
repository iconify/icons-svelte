<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frp_2fbhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="frp_2fbhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:align-right" {...props}></Icon>
