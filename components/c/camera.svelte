<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c93l_8bfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c93l_8bfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:camera" {...props}></Icon>
