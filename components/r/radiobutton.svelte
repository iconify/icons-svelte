<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sp934ebga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sp934ebga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:radiobutton" {...props}></Icon>
