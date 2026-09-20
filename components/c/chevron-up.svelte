<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvrg0dbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tvrg0dbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:chevron-up" {...props}></Icon>
