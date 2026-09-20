<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emz203hin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="emz203hin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:open-in-new-window" {...props}></Icon>
