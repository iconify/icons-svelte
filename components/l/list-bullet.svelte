<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wco3rcpyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wco3rcpyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:list-bullet" {...props}></Icon>
