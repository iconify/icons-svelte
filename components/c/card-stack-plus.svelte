<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg7n7en_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xg7n7en_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:card-stack-plus" {...props}></Icon>
