<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3p6w_dsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="w3p6w_dsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:dot-filled" {...props}></Icon>
