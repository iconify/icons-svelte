<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_1ednbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v_1ednbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:cross-2" {...props}></Icon>
