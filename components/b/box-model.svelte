<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrrfv2bak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zrrfv2bak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:box-model" {...props}></Icon>
