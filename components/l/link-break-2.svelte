<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/il39xh8sk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="il39xh8sk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:link-break-2" {...props}></Icon>
