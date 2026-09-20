<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yq2newv_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yq2newv_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:container" {...props}></Icon>
