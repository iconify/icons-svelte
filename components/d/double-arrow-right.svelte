<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxv9kabbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jxv9kabbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:double-arrow-right" {...props}></Icon>
