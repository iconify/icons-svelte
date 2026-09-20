<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn9yuy7we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zn9yuy7we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:input" {...props}></Icon>
