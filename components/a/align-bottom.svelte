<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciix0zmih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ciix0zmih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:align-bottom" {...props}></Icon>
