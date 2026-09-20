<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edl-dmbxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="edl-dmbxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:github-logo" {...props}></Icon>
