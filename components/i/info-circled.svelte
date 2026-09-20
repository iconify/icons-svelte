<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvqs58b1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="uvqs58b1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:info-circled" {...props}></Icon>
