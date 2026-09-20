<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/ql-f45b9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ql-f45b9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:blending-mode" {...props}></Icon>
