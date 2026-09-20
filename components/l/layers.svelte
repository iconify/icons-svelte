<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hxw46px4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hxw46px4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:layers" {...props}></Icon>
