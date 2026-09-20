<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c154ibczc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c154ibczc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:align-center-horizontally" {...props}></Icon>
