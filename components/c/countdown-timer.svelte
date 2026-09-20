<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt1np09fu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tt1np09fu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:countdown-timer" {...props}></Icon>
