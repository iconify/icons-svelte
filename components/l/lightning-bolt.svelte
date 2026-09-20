<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di4r6q8zq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="di4r6q8zq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:lightning-bolt" {...props}></Icon>
