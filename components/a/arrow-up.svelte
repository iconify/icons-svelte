<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmpwi8b8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dmpwi8b8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:arrow-up" {...props}></Icon>
