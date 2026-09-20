<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnxm2eb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gnxm2eb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:arrow-bottom-right" {...props}></Icon>
