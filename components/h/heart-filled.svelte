<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/woe5-fbql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="woe5-fbql"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:heart-filled" {...props}></Icon>
