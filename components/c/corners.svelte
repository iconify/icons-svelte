<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9rz68q5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w9rz68q5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:corners" {...props}></Icon>
