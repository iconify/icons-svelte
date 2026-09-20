<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1p-jyv8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w1p-jyv8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:avatar" {...props}></Icon>
