<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgblf3b3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tgblf3b3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:linkedin-logo" {...props}></Icon>
