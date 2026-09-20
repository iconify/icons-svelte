<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy_a9mbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qy_a9mbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:arrow-top-right" {...props}></Icon>
