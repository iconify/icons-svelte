<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwr2zcchh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vwr2zcchh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:columns" {...props}></Icon>
