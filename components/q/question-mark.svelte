<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wta6cob2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wta6cob2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:question-mark" {...props}></Icon>
